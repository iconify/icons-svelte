<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x49bj1boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x49bj1boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:phabricator" {...props}></Icon>
