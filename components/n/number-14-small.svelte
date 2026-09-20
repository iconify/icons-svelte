<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghb64morl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghb64morl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-14-small" {...props}></Icon>
