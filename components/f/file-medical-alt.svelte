<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukw76obbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukw76obbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-medical-alt" {...props}></Icon>
