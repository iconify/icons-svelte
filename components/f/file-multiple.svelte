<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeg8hro-s.css';
import '../../css/b/b7-je_b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eeg8hro-s"/><path class="b7-je_b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:file-multiple" {...props}></Icon>
