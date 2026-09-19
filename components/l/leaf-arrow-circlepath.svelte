<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_mec57ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="y_mec57ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:leaf-arrow-circlepath" {...props}></Icon>
