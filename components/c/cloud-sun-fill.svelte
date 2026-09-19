<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbu6-s_cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jbu6-s_cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-sun-fill" {...props}></Icon>
