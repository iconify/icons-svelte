<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qezco3lak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qezco3lak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:clipboard-blank" {...props}></Icon>
