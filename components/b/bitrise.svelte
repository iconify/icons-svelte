<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za24fypym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="za24fypym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:bitrise" {...props}></Icon>
