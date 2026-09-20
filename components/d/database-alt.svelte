<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eplmzlbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eplmzlbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:database-alt" {...props}></Icon>
