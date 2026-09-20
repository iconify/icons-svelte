<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9updbbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9updbbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:activitypub" {...props}></Icon>
