<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr8r8gbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr8r8gbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nuxt" {...props}></Icon>
