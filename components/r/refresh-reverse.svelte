<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1jznez-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-2.5};
const content = `<path class="v1jznez-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:refresh-reverse" {...props}></Icon>
