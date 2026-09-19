<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-2e-4bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-2e-4bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:folder-plus-filled" {...props}></Icon>
