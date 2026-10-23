<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umyq7pbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umyq7pbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cake-slice" {...props}></Icon>
