<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsr4q-iac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsr4q-iac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:feel-at-ease-filled" {...props}></Icon>
