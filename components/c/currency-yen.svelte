<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcapv9ssm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcapv9ssm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:currency-yen" {...props}></Icon>
