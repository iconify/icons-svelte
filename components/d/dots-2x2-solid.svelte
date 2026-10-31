<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhg06p-ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhg06p-ko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-2x2-solid" {...props}></Icon>
