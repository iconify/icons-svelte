<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sai67h5sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sai67h5sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbells-outline" {...props}></Icon>
