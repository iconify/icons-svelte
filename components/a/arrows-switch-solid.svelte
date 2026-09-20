<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgihqvbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgihqvbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrows-switch-solid" {...props}></Icon>
