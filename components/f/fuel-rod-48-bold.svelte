<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj3ip275j.css';
import '../../css/k/kumpysh-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dj3ip275j"/><path class="kumpysh-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-rod-48-bold" {...props}></Icon>
