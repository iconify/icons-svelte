<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiaq27v-e.css';
import '../../css/b/b0rftsbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tiaq27v-e"/><path class="b0rftsbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:compass-light" {...props}></Icon>
