<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpa6-tfum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpa6-tfum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:italic-fill" {...props}></Icon>
