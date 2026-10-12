<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed-8irbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ed-8irbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:briefcase-medical-filled" {...props}></Icon>
