<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2q_mob-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2q_mob-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-up" {...props}></Icon>
