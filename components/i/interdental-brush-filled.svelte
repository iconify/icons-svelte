<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktp477bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktp477bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:interdental-brush-filled" {...props}></Icon>
