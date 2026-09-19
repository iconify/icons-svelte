<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1k9bac8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s1k9bac8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-checkmark-circle" {...props}></Icon>
