<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig0hw9b-i.css';
import '../../css/j/jjz706w_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig0hw9b-i"/><path class="jjz706w_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-translation-api" {...props}></Icon>
