<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqb3qcc7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqb3qcc7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:dot-02-s" {...props}></Icon>
