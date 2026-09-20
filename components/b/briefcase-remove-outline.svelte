<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz_l2cbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz_l2cbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase-remove-outline" {...props}></Icon>
