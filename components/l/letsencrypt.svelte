<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahmj-4bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahmj-4bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:letsencrypt" {...props}></Icon>
