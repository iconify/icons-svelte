<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjc94rm5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjc94rm5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:command-fill" {...props}></Icon>
