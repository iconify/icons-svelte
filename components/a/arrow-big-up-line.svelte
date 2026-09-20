<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdapn3bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdapn3bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-big-up-line" {...props}></Icon>
