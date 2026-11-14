<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9nnej6xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9nnej6xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:delete-04" {...props}></Icon>
