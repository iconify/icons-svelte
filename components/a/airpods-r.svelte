<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojr94bcww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojr94bcww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:airpods-r" {...props}></Icon>
