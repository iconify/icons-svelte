<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-u7flbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-u7flbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:git-pull-request-arrow" {...props}></Icon>
