<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr03lx9eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fr03lx9eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:formula" {...props}></Icon>
