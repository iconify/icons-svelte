<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_xt6zhqo.css';
import '../../css/c/c1okp3bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l_xt6zhqo"/><path class="c1okp3bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:briefcase-48-bold" {...props}></Icon>
