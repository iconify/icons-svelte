<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grjwqbcjo.css';
import '../../css/t/tbbjvyiok.css';
import '../../css/u/ux3ufdb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="grjwqbcjo"/><path class="tbbjvyiok"/><path class="ux3ufdb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:respiratory" {...props}></Icon>
