<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0ndb3slp.css';
import '../../css/v/vpm5wbcdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="j0ndb3slp"/><path class="vpm5wbcdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:okta-wordmark" {...props}></Icon>
