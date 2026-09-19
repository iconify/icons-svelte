<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/attzhvbqz.css';
import '../../css/v/vzeo59nus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="attzhvbqz"/><path class="vzeo59nus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chevrons-right-filled" {...props}></Icon>
