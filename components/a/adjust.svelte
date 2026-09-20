<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2z_0u2cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h2z_0u2cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:adjust" {...props}></Icon>
