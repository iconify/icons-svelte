<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp_741pqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp_741pqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:profile-card-outline" {...props}></Icon>
