<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drmnp89cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="drmnp89cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-badge-fill-12" {...props}></Icon>
