<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da2byub9q.css';
import '../../css/c/c5u4wmg9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="da2byub9q"/><path class="c5u4wmg9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heading-48" {...props}></Icon>
