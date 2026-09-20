<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhk4w5u-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhk4w5u-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:expand-vertical-light" {...props}></Icon>
