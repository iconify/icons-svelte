<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3ltwuydz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3ltwuydz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bottle-glass-fill" {...props}></Icon>
