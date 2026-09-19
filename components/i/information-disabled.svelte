<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/outcig9zn.css';
import '../../css/i/i0orfx9cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="outcig9zn"/><path class="i0orfx9cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:information-disabled" {...props}></Icon>
