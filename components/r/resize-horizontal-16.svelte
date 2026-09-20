<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0tpdz_cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d0tpdz_cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:resize-horizontal-16" {...props}></Icon>
