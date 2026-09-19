<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7-z66pkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o7-z66pkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:indent-left" {...props}></Icon>
