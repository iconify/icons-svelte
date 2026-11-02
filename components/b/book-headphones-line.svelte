<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhx2a_1cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhx2a_1cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-headphones-line" {...props}></Icon>
