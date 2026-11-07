<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7lt-t-fe.css';
import '../../css/b/b-rzfvbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7lt-t-fe"/><path class="b-rzfvbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:braces-outline" {...props}></Icon>
