<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1ll5c1cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d1ll5c1cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:python" {...props}></Icon>
