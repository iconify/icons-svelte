<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0-k9nbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0-k9nbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrows-v-alt" {...props}></Icon>
