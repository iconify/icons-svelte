<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4fer0abt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u4fer0abt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-sort-v-filled" {...props}></Icon>
