<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx4e6vbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sx4e6vbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fpis" {...props}></Icon>
