<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqu1h4boa.css';
import '../../css/w/w5v5asbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqu1h4boa"/><path class="w5v5asbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-edit" {...props}></Icon>
