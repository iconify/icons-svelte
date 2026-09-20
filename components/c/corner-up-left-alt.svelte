<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra4h__bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra4h__bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:corner-up-left-alt" {...props}></Icon>
