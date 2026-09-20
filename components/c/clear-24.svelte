<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvhzlphhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mvhzlphhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:clear-24" {...props}></Icon>
