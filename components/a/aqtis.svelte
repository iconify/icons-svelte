<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-7eiub-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o-7eiub-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:aqtis" {...props}></Icon>
