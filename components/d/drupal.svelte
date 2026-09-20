<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwve77bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwve77bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:drupal" {...props}></Icon>
