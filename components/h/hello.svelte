<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzw2v0c9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:hello" {...props}></Icon>
<style>
:global(.bzw2v0c9x) {
  d: path("M7.237 4.368a8.992 8.992 0 0 0 0 15.264zm3.175 16.492a9 9 0 0 0 3.176 0v-6.67l-3.176.407zm6.351-1.228a8.992 8.992 0 0 0 0-15.264zM13.588 3.14v7.88l-3.176.45V3.14a9 9 0 0 1 3.176 0");
}

</style>
