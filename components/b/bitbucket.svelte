<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a30no-b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a30no-b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:bitbucket" {...props}></Icon>
