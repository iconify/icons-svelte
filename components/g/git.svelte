<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlji09d4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlji09d4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:git" {...props}></Icon>
