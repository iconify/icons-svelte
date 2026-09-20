<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amsxbvear.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amsxbvear"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:arrow-right-24" {...props}></Icon>
