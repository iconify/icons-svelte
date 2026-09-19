<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq_sz_0cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="jq_sz_0cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:a-upper-case" {...props}></Icon>
