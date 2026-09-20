<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i62i6jc8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i62i6jc8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:asterisk" {...props}></Icon>
