<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6-cancaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6-cancaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:bullet-list-solid" {...props}></Icon>
