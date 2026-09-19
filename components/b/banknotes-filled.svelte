<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5xb7ebsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5xb7ebsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:banknotes-filled" {...props}></Icon>
