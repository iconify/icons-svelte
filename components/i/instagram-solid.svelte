<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1imkf3hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1imkf3hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:instagram-solid" {...props}></Icon>
