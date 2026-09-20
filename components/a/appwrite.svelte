<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/danba2wvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="danba2wvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:appwrite" {...props}></Icon>
