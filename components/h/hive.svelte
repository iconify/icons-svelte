<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-t-q3bzs.css';
import '../../css/s/s3ofesarg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-t-q3bzs"/><path class="s3ofesarg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hive" {...props}></Icon>
