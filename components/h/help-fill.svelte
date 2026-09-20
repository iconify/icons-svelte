<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olgsfvb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="olgsfvb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:help-fill" {...props}></Icon>
