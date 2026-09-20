<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brw66jb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="brw66jb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:jira-software-logo-2-block" {...props}></Icon>
