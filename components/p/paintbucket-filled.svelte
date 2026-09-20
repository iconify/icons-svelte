<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npf7jgx5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npf7jgx5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:paintbucket-filled" {...props}></Icon>
