<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf_am2bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":460,"height":512};
const content = `<path class="cf_am2bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:mruby" {...props}></Icon>
