<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htgbsacnp.css';
import '../../css/y/ypfktcc0d.css';
import '../../css/d/dd9yyy66g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="htgbsacnp"/><path class="ypfktcc0d"/><path class="dd9yyy66g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:news" {...props}></Icon>
