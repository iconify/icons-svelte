<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwi8-ubww.css';
import '../../css/a/a3qgfdcno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwi8-ubww"/><path class="a3qgfdcno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:azit" {...props}></Icon>
