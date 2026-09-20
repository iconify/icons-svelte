<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck-rj9bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck-rj9bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-hiflow" {...props}></Icon>
