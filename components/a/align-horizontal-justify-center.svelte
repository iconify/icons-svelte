<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/othkmjxvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="othkmjxvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-horizontal-justify-center" {...props}></Icon>
