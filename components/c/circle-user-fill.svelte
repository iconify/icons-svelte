<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf8pdo8gg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mf8pdo8gg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-user-fill" {...props}></Icon>
