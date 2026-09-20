<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j23jfj2cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="j23jfj2cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:chevron-down-small" {...props}></Icon>
