<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn5gkh4pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yn5gkh4pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:octagon-x-fill" {...props}></Icon>
