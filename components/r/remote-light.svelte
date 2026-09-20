<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb8t19bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb8t19bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:remote-light" {...props}></Icon>
