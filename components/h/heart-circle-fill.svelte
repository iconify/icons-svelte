<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb870rb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qb870rb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:heart-circle-fill" {...props}></Icon>
