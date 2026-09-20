<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kscz-0cog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kscz-0cog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:play" {...props}></Icon>
