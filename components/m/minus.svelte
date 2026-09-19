<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b77c3o1cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b77c3o1cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:minus" {...props}></Icon>
