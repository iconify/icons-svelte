<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deexg9_cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="deexg9_cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:check-all" {...props}></Icon>
