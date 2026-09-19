<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_ivf9oak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_ivf9oak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:caret-left-outline" {...props}></Icon>
