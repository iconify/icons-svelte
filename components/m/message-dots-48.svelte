<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me-xmbmth.css';
import '../../css/a/a_pmb6bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="me-xmbmth"/><path class="a_pmb6bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-dots-48" {...props}></Icon>
