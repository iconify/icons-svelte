<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzqj8o9cj.css';
import '../../css/v/v8rh_m67z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kzqj8o9cj"/><path class="v8rh_m67z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:protractor-48" {...props}></Icon>
