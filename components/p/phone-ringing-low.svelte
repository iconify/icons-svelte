<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit0tnbsg.css';
import '../../css/t/tag3qab8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hit0tnbsg"/><path class="tag3qab8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:phone-ringing-low" {...props}></Icon>
