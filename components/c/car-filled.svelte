<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf11o55rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf11o55rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:car-filled" {...props}></Icon>
