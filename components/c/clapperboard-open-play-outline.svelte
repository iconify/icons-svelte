<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl-vh0b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gl-vh0b0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clapperboard-open-play-outline" {...props}></Icon>
