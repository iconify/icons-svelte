<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ara_c1bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ara_c1bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:relation-one-to-one-filled" {...props}></Icon>
