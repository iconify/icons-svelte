<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eotl5ccee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="eotl5ccee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:person-crop-square-fill" {...props}></Icon>
