<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o47fwqmzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o47fwqmzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:minus" {...props}></Icon>
