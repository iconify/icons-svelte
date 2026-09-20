<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csj82-bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csj82-bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:divide" {...props}></Icon>
