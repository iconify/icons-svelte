<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qks8ej-gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qks8ej-gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:langchaincorporate" {...props}></Icon>
