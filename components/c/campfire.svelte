<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbiu97owb.css';
import '../../css/k/kti4eo0qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbiu97owb"/><path class="kti4eo0qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:campfire" {...props}></Icon>
