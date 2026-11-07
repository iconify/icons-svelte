<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoshjbpvd.css';
import '../../css/b/bt37pjbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoshjbpvd"/><path class="bt37pjbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:check-bold-duotone" {...props}></Icon>
