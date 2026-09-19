<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm_kdgbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm_kdgbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:delete-row" {...props}></Icon>
