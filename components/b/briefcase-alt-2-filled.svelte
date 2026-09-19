<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vamcxub9f.css';
import '../../css/i/i7a-gbc6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vamcxub9f"/><path class="i7a-gbc6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:briefcase-alt-2-filled" {...props}></Icon>
