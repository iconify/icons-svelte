<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6ygb96zu.css';
import '../../css/s/saol7rb8i.css';
import '../../css/h/h49yzab-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v6ygb96zu"/><path class="saol7rb8i"/><path class="h49yzab-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:person-with-white-cane-facing-right" {...props}></Icon>
